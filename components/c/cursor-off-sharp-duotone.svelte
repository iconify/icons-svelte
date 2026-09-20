<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fduz3ccfo.css';
import '../../css/v/v5ezk3k3l.css';
import '../../css/k/km1bwubkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fduz3ccfo"/><path class="v5ezk3k3l"/><path class="km1bwubkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-off-sharp-duotone" {...props}></Icon>
