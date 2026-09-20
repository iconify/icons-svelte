<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxb8sdb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fxb8sdb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:pylon" {...props}></Icon>
