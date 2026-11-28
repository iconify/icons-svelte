<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpf0_218d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lpf0_218d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-warning-fill" {...props}></Icon>
