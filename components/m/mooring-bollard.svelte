<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh1-gqbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh1-gqbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mooring-bollard" {...props}></Icon>
