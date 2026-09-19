<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw37cbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ulw37cbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:domino-mask" {...props}></Icon>
