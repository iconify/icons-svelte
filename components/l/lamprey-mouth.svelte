<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz3vbkbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz3vbkbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lamprey-mouth" {...props}></Icon>
