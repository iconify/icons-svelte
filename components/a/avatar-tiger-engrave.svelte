<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vys_njbbu.css';
import '../../css/b/b34zc16tc.css';
import '../../css/b/bncus0vco.css';
import '../../css/s/ssadnlb_w.css';
import '../../css/r/r2o5n7qei.css';
import '../../css/p/plwqyqbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vys_njbbu wm-k"/><path class="b34zc16tc wm-a"/><path class="bncus0vco wm-shadow"/><path class="ssadnlb_w wm-k"/><path class="r2o5n7qei wm-k"/><path class="plwqyqbee wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-tiger-engrave" {...props}></Icon>
