<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbu0fetxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gbu0fetxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:houndci" {...props}></Icon>
