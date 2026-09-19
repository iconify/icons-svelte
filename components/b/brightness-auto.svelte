<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk8kwsb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="zk8kwsb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-auto" {...props}></Icon>
