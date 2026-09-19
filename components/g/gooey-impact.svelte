<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmknib4fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmknib4fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gooey-impact" {...props}></Icon>
