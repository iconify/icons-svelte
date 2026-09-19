<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgh5s1vxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgh5s1vxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-049" {...props}></Icon>
