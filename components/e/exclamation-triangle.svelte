<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiu4lcw5h.css';
import '../../css/e/e0la5wsre.css';
import '../../css/r/rz3ur5bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tiu4lcw5h"/><path class="e0la5wsre"/><ellipse class="rz3ur5bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:exclamation-triangle" {...props}></Icon>
