<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iub6988rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iub6988rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dot-circle" {...props}></Icon>
