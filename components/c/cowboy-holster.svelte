<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7jdv5g2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h7jdv5g2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cowboy-holster" {...props}></Icon>
