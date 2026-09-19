<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kymg-qb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kymg-qb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:camera-video-fill" {...props}></Icon>
