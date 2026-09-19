<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvy7ldnxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvy7ldnxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:focused-lightning" {...props}></Icon>
