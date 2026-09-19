<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ilai0fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2ilai0fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:icicles-aura" {...props}></Icon>
