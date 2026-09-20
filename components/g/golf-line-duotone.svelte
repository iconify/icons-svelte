<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f2jbpwb_z.css';
import '../../css/y/ya4v2ogmm.css';
import '../../css/m/mxy6aifea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><ellipse class="f2jbpwb_z"/><path class="ya4v2ogmm"/><path class="mxy6aifea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:golf-line-duotone" {...props}></Icon>
