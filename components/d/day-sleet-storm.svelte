<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_a6-ubkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="d_a6-ubkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-sleet-storm" {...props}></Icon>
