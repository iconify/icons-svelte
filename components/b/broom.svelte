<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmt269wze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmt269wze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:broom" {...props}></Icon>
