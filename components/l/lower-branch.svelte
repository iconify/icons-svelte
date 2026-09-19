<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x_-2nnb_l.css';
import '../../css/a/awp_-7bqo.css';
import '../../css/u/usb05nn8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="x_-2nnb_l"/><circle transform="matrix(0 1 1 0 24 9)" class="awp_-7bqo"/><path class="usb05nn8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:lower-branch" {...props}></Icon>
