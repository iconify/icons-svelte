<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz4rlx_oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fz4rlx_oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:incubator" {...props}></Icon>
