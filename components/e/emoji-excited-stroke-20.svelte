<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5dk3pbjk.css';
import '../../css/j/jpdmwmb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u5dk3pbjk"/><path class="jpdmwmb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-excited-stroke-20" {...props}></Icon>
