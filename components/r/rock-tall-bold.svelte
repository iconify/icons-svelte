<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd_m2db3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bd_m2db3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock-tall-bold" {...props}></Icon>
