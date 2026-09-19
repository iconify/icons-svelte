<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgore1bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgore1bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:granary" {...props}></Icon>
