<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-908bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly-908bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:executioner-hood" {...props}></Icon>
