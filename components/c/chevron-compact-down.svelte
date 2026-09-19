<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5e1o2yxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z5e1o2yxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-compact-down" {...props}></Icon>
