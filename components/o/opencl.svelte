<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdf5exf4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdf5exf4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:opencl" {...props}></Icon>
