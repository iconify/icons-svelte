<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tilsz0f6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tilsz0f6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kitchen-tap" {...props}></Icon>
