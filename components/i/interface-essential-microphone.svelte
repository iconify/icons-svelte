<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0isofspd.css';
import '../../css/u/usr-jnz4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0isofspd"/><path class="usr-jnz4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-microphone" {...props}></Icon>
