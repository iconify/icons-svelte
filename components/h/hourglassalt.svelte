<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr3zg3byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zr3zg3byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hourglassalt" {...props}></Icon>
