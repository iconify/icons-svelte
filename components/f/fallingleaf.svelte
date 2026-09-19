<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2pr8hokp.css';
import '../../css/j/jswp7mbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2pr8hokp"/><path class="jswp7mbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fallingleaf" {...props}></Icon>
