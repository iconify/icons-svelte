<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t58isqm6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t58isqm6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bracer" {...props}></Icon>
