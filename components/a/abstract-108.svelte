<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao0ucxbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ao0ucxbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-108" {...props}></Icon>
