<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-ffxoext.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-ffxoext"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:orrery" {...props}></Icon>
