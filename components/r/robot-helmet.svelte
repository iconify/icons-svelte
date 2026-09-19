<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-yle1b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-yle1b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robot-helmet" {...props}></Icon>
