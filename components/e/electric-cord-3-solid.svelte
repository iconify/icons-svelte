<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipcy7l2ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipcy7l2ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:electric-cord-3-solid" {...props}></Icon>
