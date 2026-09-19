<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1wyn0pqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1wyn0pqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:high-kick" {...props}></Icon>
