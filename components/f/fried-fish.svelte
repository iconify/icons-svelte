<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf5msobie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf5msobie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fried-fish" {...props}></Icon>
