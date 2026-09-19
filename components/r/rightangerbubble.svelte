<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it48t2bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="it48t2bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rightangerbubble" {...props}></Icon>
