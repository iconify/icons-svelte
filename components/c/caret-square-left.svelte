<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ury1xy_5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ury1xy_5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:caret-square-left" {...props}></Icon>
