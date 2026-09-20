<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3t2t0bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3t2t0bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flashpaper-dark" {...props}></Icon>
