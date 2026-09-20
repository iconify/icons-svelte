<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4kanwwph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="t4kanwwph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-windy" {...props}></Icon>
