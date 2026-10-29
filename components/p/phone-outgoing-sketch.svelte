<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w328ithck.css';
import '../../css/d/dqwndkx9y.css';
import '../../css/q/ql7xkx99v.css';
import '../../css/l/lwpbxcrve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w328ithck"/><path class="dqwndkx9y wm-s"/><path class="ql7xkx99v wm-k"/><path class="lwpbxcrve wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-outgoing-sketch" {...props}></Icon>
