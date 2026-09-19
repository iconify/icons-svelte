<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icy086bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icy086bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:easter-egg" {...props}></Icon>
