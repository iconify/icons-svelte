<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9z-6laaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9z-6laaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:liquid-soap" {...props}></Icon>
