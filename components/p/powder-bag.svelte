<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds02b5bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds02b5bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:powder-bag" {...props}></Icon>
