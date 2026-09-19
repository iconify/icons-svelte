<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocssg7g_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ocssg7g_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:bluetooth-b" {...props}></Icon>
