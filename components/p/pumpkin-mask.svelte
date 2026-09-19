<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e96ji41bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e96ji41bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pumpkin-mask" {...props}></Icon>
