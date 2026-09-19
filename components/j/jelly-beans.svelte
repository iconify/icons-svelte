<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7ge6771m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k7ge6771m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jelly-beans" {...props}></Icon>
