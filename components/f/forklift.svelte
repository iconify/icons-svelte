<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8m4j_b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8m4j_b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:forklift" {...props}></Icon>
