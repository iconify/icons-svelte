<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk2c879cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk2c879cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:antibody" {...props}></Icon>
