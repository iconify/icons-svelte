<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knfdt1uek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knfdt1uek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:moebius-star" {...props}></Icon>
