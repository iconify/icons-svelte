<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n032jcw_n.css';
import '../../css/i/i-ko7r1rt.css';
import '../../css/f/f3qmz0s7a.css';
import '../../css/a/aomk_sbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n032jcw_n"/><path class="i-ko7r1rt wm-a"/><path class="f3qmz0s7a wm-k"/><path class="aomk_sbrv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bot-sketch" {...props}></Icon>
