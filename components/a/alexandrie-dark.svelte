<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd1k3d-vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sd1k3d-vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alexandrie-dark" {...props}></Icon>
