<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uca9trmme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uca9trmme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cycle" {...props}></Icon>
