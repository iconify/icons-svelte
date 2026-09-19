<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n-cf0tyaw.css';
import '../../css/n/nwun370oi.css';
import '../../css/g/gk6535bxo.css';
import '../../css/a/aw0dy7lpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n-cf0tyaw"/><path class="nwun370oi"/><path class="gk6535bxo"/><path class="aw0dy7lpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-upscale" {...props}></Icon>
