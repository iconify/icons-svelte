<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4fw_vbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4fw_vbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six" {...props}></Icon>
