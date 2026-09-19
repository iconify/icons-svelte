<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeuq6bc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jeuq6bc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:box-cutter" {...props}></Icon>
