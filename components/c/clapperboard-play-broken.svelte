<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ykueg1b1u.css';
import '../../css/n/nr7t2bb1e.css';
import '../../css/z/zght4ub1f.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/l/l6e0kx4od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ykueg1b1u"/><path class="nr7t2bb1e"/><path class="zght4ub1f"/><path class="si_mtzbvj"/><path class="l6e0kx4od"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-play-broken" {...props}></Icon>
