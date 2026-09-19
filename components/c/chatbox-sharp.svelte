<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6lcxb24u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6lcxb24u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chatbox-sharp" {...props}></Icon>
