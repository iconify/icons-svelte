<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbz72vbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zbz72vbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:bimobject" {...props}></Icon>
