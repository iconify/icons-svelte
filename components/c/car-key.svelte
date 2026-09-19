<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn3x2lbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn3x2lbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:car-key" {...props}></Icon>
