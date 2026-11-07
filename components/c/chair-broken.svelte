<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zzd2qnarn.css';
import '../../css/b/b0469bblh.css';
import '../../css/d/dp6f7rbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zzd2qnarn"/><path class="b0469bblh"/><path class="dp6f7rbss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-broken" {...props}></Icon>
