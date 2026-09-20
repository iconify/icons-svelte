<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxp_ne7lq.css';
import '../../css/i/ik8lqcbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mxp_ne7lq"/><path clip-rule="evenodd" class="ik8lqcbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drumkit-16" {...props}></Icon>
