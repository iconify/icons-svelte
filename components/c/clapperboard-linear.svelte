<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/r/rcdawhb0x.css';
import '../../css/y/ykueg1b1u.css';
import '../../css/n/nr7t2bb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="rcdawhb0x"/><path class="ykueg1b1u"/><path class="nr7t2bb1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-linear" {...props}></Icon>
