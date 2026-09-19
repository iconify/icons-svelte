<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okxe_6bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okxe_6bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:buy-card" {...props}></Icon>
