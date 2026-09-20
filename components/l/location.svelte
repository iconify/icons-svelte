<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtwew_qxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rtwew_qxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:location" {...props}></Icon>
