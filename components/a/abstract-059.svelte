<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnbm68e6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gnbm68e6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-059" {...props}></Icon>
