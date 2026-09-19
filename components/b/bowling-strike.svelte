<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfduo9w_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfduo9w_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bowling-strike" {...props}></Icon>
