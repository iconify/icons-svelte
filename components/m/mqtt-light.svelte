<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pprnic1yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pprnic1yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mqtt-light" {...props}></Icon>
