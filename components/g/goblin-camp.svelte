<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocj48bc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocj48bc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:goblin-camp" {...props}></Icon>
