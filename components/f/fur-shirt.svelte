<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly5--pdrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly5--pdrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fur-shirt" {...props}></Icon>
