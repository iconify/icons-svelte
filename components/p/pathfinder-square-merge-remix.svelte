<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jekcgwb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jekcgwb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-square-merge-remix" {...props}></Icon>
