<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koxstha1f.css';
import '../../css/v/vpp78ggra.css';
import '../../css/w/w2y3zvo5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="koxstha1f"/><path class="vpp78ggra"/><path class="w2y3zvo5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emulatorjs" {...props}></Icon>
