<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2dgmq29u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2dgmq29u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:large-paint-brush" {...props}></Icon>
