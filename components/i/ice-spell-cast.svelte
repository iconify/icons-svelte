<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw06pbbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mw06pbbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-spell-cast" {...props}></Icon>
