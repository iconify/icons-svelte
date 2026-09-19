<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcmd7lykp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcmd7lykp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:fullscreen-exit" {...props}></Icon>
