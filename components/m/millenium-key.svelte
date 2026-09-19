<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eljshwb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eljshwb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:millenium-key" {...props}></Icon>
