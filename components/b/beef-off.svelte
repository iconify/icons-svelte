<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/d7_zg5lyr.css';
import '../../css/r/ra8ngubdl.css';
import '../../css/m/mfhnhdc3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d7_zg5lyr"/><path class="ra8ngubdl"/><path class="mfhnhdc3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:beef-off" {...props}></Icon>
