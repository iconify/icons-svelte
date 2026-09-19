<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_2ozb4w.css';
import '../../css/f/famexubdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zp_2ozb4w"/><path class="famexubdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:graph-trend" {...props}></Icon>
