<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9x4_cb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="d9x4_cb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:jug-detergent" {...props}></Icon>
