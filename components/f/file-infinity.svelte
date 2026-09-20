<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/l72ym8u0j.css';
import '../../css/f/fwo4s-hri.css';
import '../../css/t/t_3o8abnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l72ym8u0j"/><path class="fwo4s-hri"/><path class="t_3o8abnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-infinity" {...props}></Icon>
