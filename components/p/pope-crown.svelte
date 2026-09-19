<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji4w1hy1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji4w1hy1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pope-crown" {...props}></Icon>
