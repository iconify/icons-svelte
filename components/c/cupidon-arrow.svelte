<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff-4-q9jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff-4-q9jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cupidon-arrow" {...props}></Icon>
