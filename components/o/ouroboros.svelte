<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldygpjinh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ldygpjinh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ouroboros" {...props}></Icon>
