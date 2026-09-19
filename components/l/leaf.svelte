<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwnj6q1-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zwnj6q1-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:leaf" {...props}></Icon>
