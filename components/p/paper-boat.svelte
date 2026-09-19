<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jivre87yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jivre87yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-boat" {...props}></Icon>
