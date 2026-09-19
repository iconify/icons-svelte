<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fafjl7bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fafjl7bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battleship" {...props}></Icon>
