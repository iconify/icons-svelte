<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8ph2xqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nv8ph2xqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pizza-cutter" {...props}></Icon>
