<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzj-g5bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzj-g5bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kali-linux-light" {...props}></Icon>
