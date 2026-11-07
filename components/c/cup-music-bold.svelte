<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mek24e_ia.css';
import '../../css/i/i1258-uxv.css';
import '../../css/q/qwz1y-byg.css';
import '../../css/o/owtnwjtgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mek24e_ia"/><path clip-rule="evenodd" class="i1258-uxv"/><path class="qwz1y-byg"/><path class="owtnwjtgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-music-bold" {...props}></Icon>
