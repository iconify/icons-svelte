<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9z8qybkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s9z8qybkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:charged-arrow" {...props}></Icon>
