<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t57rj1bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t57rj1bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:medieval-gate" {...props}></Icon>
