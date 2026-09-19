<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imf12-b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imf12-b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-tongue-wink" {...props}></Icon>
