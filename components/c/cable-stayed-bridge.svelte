<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v70ca4k4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v70ca4k4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cable-stayed-bridge" {...props}></Icon>
