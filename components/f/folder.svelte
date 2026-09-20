<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/detlv4hxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="detlv4hxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:folder" {...props}></Icon>
