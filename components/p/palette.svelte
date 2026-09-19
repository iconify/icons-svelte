<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm7w0lb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hm7w0lb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:palette" {...props}></Icon>
