<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn93d6aes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xn93d6aes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:indent-left" {...props}></Icon>
