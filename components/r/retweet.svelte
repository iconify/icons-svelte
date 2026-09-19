<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzz5_vbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lzz5_vbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:retweet" {...props}></Icon>
