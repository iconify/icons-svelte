<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn-5o7bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jn-5o7bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bookmark-outline" {...props}></Icon>
