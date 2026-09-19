<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx3is3rfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx3is3rfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-trident" {...props}></Icon>
