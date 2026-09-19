<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yy8jbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6yy8jbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:border-left" {...props}></Icon>
