<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c8i5flb4l.css';
import '../../css/a/acc9nobeq.css';
import '../../css/x/xbkcgpbuj.css';
import '../../css/y/yft4l7x7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c8i5flb4l wm-deco"/><path class="acc9nobeq wm-k"/><path class="wm-a xbkcgpbuj"/><circle class="wm-s yft4l7x7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rakhi-sketch" {...props}></Icon>
