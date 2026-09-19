<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgw9obqmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgw9obqmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-034" {...props}></Icon>
