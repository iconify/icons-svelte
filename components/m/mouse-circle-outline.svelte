<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7_8g7q5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7_8g7q5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-circle-outline" {...props}></Icon>
