<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xef-lsb9x.css';
import '../../css/r/rnn19t8kn.css';
import '../../css/b/bbqj_ib9r.css';
import '../../css/c/cxmghqd7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xef-lsb9x"/><path class="rnn19t8kn wm-a"/><path class="bbqj_ib9r wm-k"/><path class="cxmghqd7h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-to-line-sketch" {...props}></Icon>
