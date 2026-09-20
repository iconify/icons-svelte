<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owku8vbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owku8vbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:appwrite-dark" {...props}></Icon>
