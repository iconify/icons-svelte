<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrzjfp6nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yrzjfp6nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-fill-16" {...props}></Icon>
