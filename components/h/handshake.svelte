<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc23b6dos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rc23b6dos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:handshake" {...props}></Icon>
