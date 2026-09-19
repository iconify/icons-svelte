<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzqfcabte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzqfcabte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-flower" {...props}></Icon>
