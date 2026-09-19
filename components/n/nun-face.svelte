<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj2i5ybtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj2i5ybtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nun-face" {...props}></Icon>
