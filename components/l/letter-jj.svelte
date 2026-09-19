<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqfa9ttux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rqfa9ttux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-jj" {...props}></Icon>
