<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ae206tbtt.css';
import '../../css/c/cg-lnu7pb.css';
import '../../css/z/zrzjcwbuq.css';
import '../../css/q/q4pv1lb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ae206tbtt"/><path class="cg-lnu7pb wm-s"/><path class="wm-k zrzjcwbuq"/><path class="q4pv1lb0v wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-missed-sketch" {...props}></Icon>
