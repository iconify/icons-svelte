<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9-d4cb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s9-d4cb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hunter-eyes" {...props}></Icon>
