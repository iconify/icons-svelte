<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buisi0gzo.css';
import '../../css/f/fvsrkp2dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="buisi0gzo"/><path class="fvsrkp2dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:education" {...props}></Icon>
