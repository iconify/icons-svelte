<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8jllh0-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v8jllh0-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-right" {...props}></Icon>
