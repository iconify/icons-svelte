<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj6a1we8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lj6a1we8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plants-and-animals" {...props}></Icon>
