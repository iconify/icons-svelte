<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r8f1pibxd.css';
import '../../css/y/y73rrwria.css';
import '../../css/c/cfp4t-bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r8f1pibxd"/><path class="wm-shadow y73rrwria"/><path class="cfp4t-bfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:blocks-engrave" {...props}></Icon>
