<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib0_6fb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib0_6fb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eight-ball" {...props}></Icon>
