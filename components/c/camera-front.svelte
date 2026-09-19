<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyj-t4bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":512};
const content = `<path class="lyj-t4bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-front" {...props}></Icon>
