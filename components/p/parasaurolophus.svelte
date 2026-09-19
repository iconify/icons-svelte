<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu6y1bchq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu6y1bchq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:parasaurolophus" {...props}></Icon>
