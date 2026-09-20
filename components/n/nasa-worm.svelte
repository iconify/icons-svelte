<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivehy_b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivehy_b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-worm" {...props}></Icon>
