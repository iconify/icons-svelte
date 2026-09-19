<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfmxfib-p.css';
import '../../css/g/go9g36_gr.css';
import '../../css/n/nodf4s9cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfmxfib-p"/><path class="go9g36_gr"/><path class="nodf4s9cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:filing" {...props}></Icon>
