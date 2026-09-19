<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx-u8bbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bx-u8bbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:buoy" {...props}></Icon>
