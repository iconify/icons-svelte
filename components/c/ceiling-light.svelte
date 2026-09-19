<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1f2_ib4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1f2_ib4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ceiling-light" {...props}></Icon>
