<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkozmf4nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rkozmf4nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-074" {...props}></Icon>
