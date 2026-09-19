<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0tegibop.css';
import '../../css/l/ln3y43bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0tegibop"/><path class="ln3y43bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:av-timer" {...props}></Icon>
