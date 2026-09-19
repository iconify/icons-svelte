<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc5-o5lsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zc5-o5lsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:growth-chart-fill-16" {...props}></Icon>
