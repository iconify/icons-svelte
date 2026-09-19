<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddsx1v0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jddsx1v0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arm" {...props}></Icon>
