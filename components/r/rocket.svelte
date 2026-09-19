<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzrofvbmd.css';
import '../../css/z/zdu6p8bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzrofvbmd"/><path class="zdu6p8bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rocket" {...props}></Icon>
