<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hllyxzboc.css';
import '../../css/m/mj_6ev9oe.css';
import '../../css/z/z1lgima0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="hllyxzboc"/><path class="mj_6ev9oe"/><path class="z1lgima0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-close-linear" {...props}></Icon>
