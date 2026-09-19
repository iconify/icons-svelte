<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0nr4c1qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0nr4c1qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burning-passion" {...props}></Icon>
