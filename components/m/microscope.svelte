<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv6d38b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv6d38b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:microscope" {...props}></Icon>
