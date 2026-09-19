<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px6o2gbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="px6o2gbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:joystick" {...props}></Icon>
