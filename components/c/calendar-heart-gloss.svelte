<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zqsvn8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5zqsvn8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-heart-gloss" {...props}></Icon>
