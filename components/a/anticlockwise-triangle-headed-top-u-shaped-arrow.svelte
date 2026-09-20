<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ievw0_bxs.css';
import '../../css/x/x5oypsb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ievw0_bxs"/><path class="x5oypsb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:anticlockwise-triangle-headed-top-u-shaped-arrow" {...props}></Icon>
