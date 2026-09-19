<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q51ogv1zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="q51ogv1zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:glass-water-droplet" {...props}></Icon>
