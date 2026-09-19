<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4qaxh9je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4qaxh9je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:iraq" {...props}></Icon>
