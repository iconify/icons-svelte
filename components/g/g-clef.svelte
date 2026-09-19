<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj1q6wbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vj1q6wbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:g-clef" {...props}></Icon>
