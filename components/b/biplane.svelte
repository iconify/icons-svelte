<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptdi0ebah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptdi0ebah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:biplane" {...props}></Icon>
