<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2vwe58tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2vwe58tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbox-ellipses" {...props}></Icon>
