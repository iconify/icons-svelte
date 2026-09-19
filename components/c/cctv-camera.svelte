<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5s7xqbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5s7xqbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cctv-camera" {...props}></Icon>
