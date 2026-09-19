<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tap41xb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tap41xb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-inside" {...props}></Icon>
