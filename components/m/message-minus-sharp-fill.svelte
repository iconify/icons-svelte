<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thll_7t1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thll_7t1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-minus-sharp-fill" {...props}></Icon>
