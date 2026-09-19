<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kk-2hwbmm.css';
import '../../css/w/wkn46nb_i.css';
import '../../css/g/gf3fkwbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="kk-2hwbmm"/><path class="wkn46nb_i"/><path class="gf3fkwbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:golf-ball" {...props}></Icon>
