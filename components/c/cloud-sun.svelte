<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfdat4jsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zfdat4jsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud-sun" {...props}></Icon>
