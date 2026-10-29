<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k5t-zhrxr.css';
import '../../css/x/xnqho3vsb.css';
import '../../css/u/u5pkhhcvy.css';
import '../../css/g/g01svf7ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k5t-zhrxr wm-a"/><path class="wm-k xnqho3vsb"/><path class="u5pkhhcvy wm-k"/><path class="g01svf7ox wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:columns-sketch" {...props}></Icon>
