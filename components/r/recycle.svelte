<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy17d2i1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gy17d2i1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:recycle" {...props}></Icon>
