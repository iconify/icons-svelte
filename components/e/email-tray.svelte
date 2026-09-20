<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tunre70_k.css';
import '../../css/f/f_afl5b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tunre70_k"/><path class="f_afl5b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-tray" {...props}></Icon>
