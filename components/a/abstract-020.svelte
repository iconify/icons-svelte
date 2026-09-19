<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai2u7s5kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ai2u7s5kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-020" {...props}></Icon>
