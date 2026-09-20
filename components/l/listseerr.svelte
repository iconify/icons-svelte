<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh9ii3etk.css';
import '../../css/n/n8lt07bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rh9ii3etk"/><path class="n8lt07bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listseerr" {...props}></Icon>
