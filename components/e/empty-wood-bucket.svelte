<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jehpac4mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jehpac4mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:empty-wood-bucket" {...props}></Icon>
