<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfc5vfbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfc5vfbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:media-document" {...props}></Icon>
