<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9a2xk5uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9a2xk5uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cricket-bat" {...props}></Icon>
