<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_hswjxlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_hswjxlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fragrance" {...props}></Icon>
