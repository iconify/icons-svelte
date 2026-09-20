<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffwtwdbhy.css';
import '../../css/e/eh0t_9g0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffwtwdbhy"/><path class="eh0t_9g0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-kubewarden" {...props}></Icon>
