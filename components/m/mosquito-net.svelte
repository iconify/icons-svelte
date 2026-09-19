<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_d4cc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yy_d4cc_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mosquito-net" {...props}></Icon>
