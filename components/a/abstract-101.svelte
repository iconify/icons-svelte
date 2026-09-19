<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkh_v5bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkh_v5bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-101" {...props}></Icon>
