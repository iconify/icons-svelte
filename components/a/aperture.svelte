<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4312iv_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4312iv_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:aperture" {...props}></Icon>
