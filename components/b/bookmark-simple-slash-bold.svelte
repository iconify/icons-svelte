<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9pp1fbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d9pp1fbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-slash-bold" {...props}></Icon>
