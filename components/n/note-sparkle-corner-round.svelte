<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpg-7bcoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpg-7bcoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-sparkle-corner-round" {...props}></Icon>
