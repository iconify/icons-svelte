<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxzb1cc6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxzb1cc6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-106" {...props}></Icon>
