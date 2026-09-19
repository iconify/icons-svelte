<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o79otvbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o79otvbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-015" {...props}></Icon>
