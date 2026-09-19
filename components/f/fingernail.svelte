<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb7xik10y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vb7xik10y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fingernail" {...props}></Icon>
