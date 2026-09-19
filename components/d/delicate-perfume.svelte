<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtw8lr04q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtw8lr04q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:delicate-perfume" {...props}></Icon>
