<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/wwc0abswz.css';
import '../../css/k/ksu4hvb6k.css';
import '../../css/s/saonk0snb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wwc0abswz"/><path class="ksu4hvb6k"/><path class="saonk0snb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-sparkles-sharp-two-tone" {...props}></Icon>
