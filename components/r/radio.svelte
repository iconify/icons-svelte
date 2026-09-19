<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie7ll2bfh.css';
import '../../css/e/ei6p82b9q.css';
import '../../css/b/bue0babum.css';
import '../../css/q/qx4ca6bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ie7ll2bfh"/><path class="ei6p82b9q"/><path class="bue0babum"/><path class="qx4ca6bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:radio" {...props}></Icon>
