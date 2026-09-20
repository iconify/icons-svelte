<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl8cagq5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8cagq5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:record-fill" {...props}></Icon>
