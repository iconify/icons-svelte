<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqjhhacny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="iqjhhacny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-circle-o-left" {...props}></Icon>
