<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-7rz3eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yg-7rz3eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-3-story-skillion-roof" {...props}></Icon>
