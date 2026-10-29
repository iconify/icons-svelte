<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sqsx9ox8k.css';
import '../../css/p/p3xx_sbre.css';
import '../../css/y/yk-er9b1u.css';
import '../../css/w/wgep9sb5p.css';
import '../../css/z/zbwddqbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sqsx9ox8k"/><path class="p3xx_sbre wm-k"/><path class="wm-a yk-er9b1u"/><path class="wgep9sb5p wm-k"/><path class="wm-a zbwddqbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:milk-sketch" {...props}></Icon>
