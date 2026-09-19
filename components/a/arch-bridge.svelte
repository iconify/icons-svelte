<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcs5uccjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fcs5uccjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arch-bridge" {...props}></Icon>
