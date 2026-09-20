<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swgykjbfw.css';
import '../../css/z/z_9dnnd4s.css';
import '../../css/f/fc28b1b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swgykjbfw"/><path class="z_9dnnd4s"/><path class="fc28b1b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:langfuse" {...props}></Icon>
