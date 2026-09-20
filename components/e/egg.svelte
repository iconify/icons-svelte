<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erxv7gxee.css';
import '../../css/m/mpm62gb7s.css';
import '../../css/k/kt1_i_bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="erxv7gxee"/><path class="mpm62gb7s"/><path class="kt1_i_bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:egg" {...props}></Icon>
