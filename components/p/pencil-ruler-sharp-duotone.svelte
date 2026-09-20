<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/ov3kx17-r.css';
import '../../css/f/fm9itxbgo.css';
import '../../css/r/r7qwbt-ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ov3kx17-r"/><path class="fm9itxbgo"/><path class="r7qwbt-ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pencil-ruler-sharp-duotone" {...props}></Icon>
