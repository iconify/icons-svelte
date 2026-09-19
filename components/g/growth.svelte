<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-wxe198h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-wxe198h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:growth" {...props}></Icon>
