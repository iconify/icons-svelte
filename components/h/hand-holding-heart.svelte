<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjyx39bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zjyx39bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-holding-heart" {...props}></Icon>
