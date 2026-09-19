<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id8ma2b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id8ma2b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:door-ring-handle" {...props}></Icon>
