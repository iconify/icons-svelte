<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfbsgfboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfbsgfboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:convince" {...props}></Icon>
