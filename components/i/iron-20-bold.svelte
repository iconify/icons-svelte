<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xldecsnzb.css';
import '../../css/v/vgmnx8bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xldecsnzb"/><path class="vgmnx8bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iron-20-bold" {...props}></Icon>
