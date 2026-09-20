<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-b1jbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j4-b1jbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-pathfinder-divide-pathfinder-divide-work" {...props}></Icon>
