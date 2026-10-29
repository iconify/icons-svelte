<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz_g4p0av.css';
import '../../css/i/it32d3oxr.css';
import '../../css/i/i9yivv3lq.css';
import '../../css/f/fkxtwmbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz_g4p0av wm-k"/><path class="it32d3oxr wm-a"/><path class="i9yivv3lq wm-a"/><path class="fkxtwmbdp wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bus" {...props}></Icon>
