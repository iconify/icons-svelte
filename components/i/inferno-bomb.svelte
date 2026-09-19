<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua8thwjmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua8thwjmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inferno-bomb" {...props}></Icon>
