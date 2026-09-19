<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7jx4s0fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g7jx4s0fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-mdx" {...props}></Icon>
