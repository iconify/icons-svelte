<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv_y32bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yv_y32bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:maze-arrow-right-short" {...props}></Icon>
