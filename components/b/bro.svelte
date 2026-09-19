<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2l3pabim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2l3pabim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bro" {...props}></Icon>
