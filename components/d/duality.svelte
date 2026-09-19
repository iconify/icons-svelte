<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r75_z_bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r75_z_bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:duality" {...props}></Icon>
