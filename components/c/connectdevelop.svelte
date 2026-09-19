<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4si8guta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="h4si8guta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:connectdevelop" {...props}></Icon>
