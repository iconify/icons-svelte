<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-j5tbb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-j5tbb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:browsers-sharp" {...props}></Icon>
