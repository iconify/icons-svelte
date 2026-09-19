<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrrbm2nes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrrbm2nes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paint-bucket" {...props}></Icon>
