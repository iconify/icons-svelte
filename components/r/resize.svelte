<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir2o0ybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ir2o0ybbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:resize" {...props}></Icon>
