<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f_ch6tbxa.css';
import '../../css/z/z_6kw01ec.css';
import '../../css/k/kf2bv0b9c.css';
import '../../css/y/yjau6mo1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f_ch6tbxa wm-k"/><path class="wm-a z_6kw01ec"/><path class="kf2bv0b9c wm-k"/><path class="wm-a yjau6mo1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:landmark-sketch" {...props}></Icon>
