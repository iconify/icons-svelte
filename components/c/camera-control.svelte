<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv0pz2b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uv0pz2b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:camera-control" {...props}></Icon>
