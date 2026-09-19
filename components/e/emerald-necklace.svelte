<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brydu94pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brydu94pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:emerald-necklace" {...props}></Icon>
