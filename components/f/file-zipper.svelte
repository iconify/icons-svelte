<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz_vukbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gz_vukbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-zipper" {...props}></Icon>
