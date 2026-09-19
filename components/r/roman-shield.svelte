<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fob3lobvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fob3lobvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:roman-shield" {...props}></Icon>
