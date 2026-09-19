<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep3ee2sbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ep3ee2sbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-sunglasses-fill" {...props}></Icon>
