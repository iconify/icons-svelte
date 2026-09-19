<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2_xoyybs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2_xoyybs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nautilus-shell" {...props}></Icon>
