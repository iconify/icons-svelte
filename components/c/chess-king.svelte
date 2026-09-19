<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2gcbl84d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2gcbl84d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chess-king" {...props}></Icon>
