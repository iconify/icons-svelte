<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq2os2btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gq2os2btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleupload" {...props}></Icon>
