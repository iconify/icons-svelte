<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0augy9ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0augy9ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cleopatra" {...props}></Icon>
