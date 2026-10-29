<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aoplr74jp.css';
import '../../css/e/etyvj2b-j.css';
import '../../css/l/lxmb61mfr.css';
import '../../css/w/wv9xrqw2w.css';
import '../../css/b/bym_ymbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aoplr74jp"/><path class="etyvj2b-j wm-k"/><path class="lxmb61mfr wm-a"/><path class="wm-k wv9xrqw2w"/><path class="bym_ymbba wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:receipt-text-sketch" {...props}></Icon>
