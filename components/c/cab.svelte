<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tujzozb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="tujzozb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cab" {...props}></Icon>
