<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjuu2tb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjuu2tb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bonsai-tree" {...props}></Icon>
