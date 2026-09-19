<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq8fi23ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq8fi23ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nuclear" {...props}></Icon>
