<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s6deurbms.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/p/pob85mb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s6deurbms"/><path class="si_mtzbvj"/><path class="pob85mb3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-broken" {...props}></Icon>
