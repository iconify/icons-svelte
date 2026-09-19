<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscks4bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vscks4bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:atlas" {...props}></Icon>
