<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0day-b1r.css';
import '../../css/r/rzjiq6ajn.css';
import '../../css/j/jce5cjb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="j0day-b1r"/><path class="rzjiq6ajn"/><path class="jce5cjb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:droplet" {...props}></Icon>
