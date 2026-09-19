<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cac5rp0ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="cac5rp0ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dollar-sign" {...props}></Icon>
