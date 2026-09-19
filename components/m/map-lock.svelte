<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-1k3_b2n.css';
import '../../css/q/qjd9umv4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="z-1k3_b2n"/><path class="qjd9umv4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-lock" {...props}></Icon>
