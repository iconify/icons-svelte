<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amm80sb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="amm80sb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-yen-yuan" {...props}></Icon>
