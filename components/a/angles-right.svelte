<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buok6acvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="buok6acvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angles-right" {...props}></Icon>
