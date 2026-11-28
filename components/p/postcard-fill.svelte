<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w94ft6b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w94ft6b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postcard-fill" {...props}></Icon>
