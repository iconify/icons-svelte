<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svt111btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svt111btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-disk-cd-2" {...props}></Icon>
