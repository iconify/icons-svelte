<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh0v953fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jh0v953fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-intersect" {...props}></Icon>
