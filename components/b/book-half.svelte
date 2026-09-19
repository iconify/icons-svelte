<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtzf6db9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dtzf6db9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:book-half" {...props}></Icon>
