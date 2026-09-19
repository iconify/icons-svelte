<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4l4ob-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zv4l4ob-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-up" {...props}></Icon>
