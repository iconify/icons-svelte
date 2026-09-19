<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iszta5b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iszta5b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:movement-sensor" {...props}></Icon>
