<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym1u7k0hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym1u7k0hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bread" {...props}></Icon>
