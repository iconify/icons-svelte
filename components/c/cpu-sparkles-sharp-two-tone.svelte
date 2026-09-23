<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/m66emgbjh.css';
import '../../css/k/ksu4hvb6k.css';
import '../../css/f/ff9zbvbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m66emgbjh"/><path class="ksu4hvb6k"/><path class="ff9zbvbzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cpu-sparkles-sharp-two-tone" {...props}></Icon>
