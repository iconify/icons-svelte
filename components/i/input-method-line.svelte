<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aph27i7aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aph27i7aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:input-method-line" {...props}></Icon>
