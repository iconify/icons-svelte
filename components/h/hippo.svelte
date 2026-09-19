<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eltjcd_fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="eltjcd_fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hippo" {...props}></Icon>
