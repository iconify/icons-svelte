<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sl1_3cb7n.css';
import '../../css/w/w5xuimedp.css';
import '../../css/f/ft3chybja.css';
import '../../css/y/ywuh7ec-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sl1_3cb7n"/><path class="w5xuimedp wm-a"/><path class="ft3chybja wm-k"/><path class="wm-a ywuh7ec-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plug-sketch" {...props}></Icon>
