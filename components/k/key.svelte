<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn_fvc00b.css';
import '../../css/s/splbbwb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wn_fvc00b"/><circle class="splbbwb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:key" {...props}></Icon>
