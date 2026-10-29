<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f810mgb8e.css';
import '../../css/q/q_de4kb_g.css';
import '../../css/g/gwtyysm7e.css';
import '../../css/a/aahfikpfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f810mgb8e wm-k"/><path class="q_de4kb_g wm-a"/><path class="gwtyysm7e wm-k"/><path class="aahfikpfy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:japanese-yen-sketch" {...props}></Icon>
