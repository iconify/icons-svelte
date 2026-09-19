<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk86-bv6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="hk86-bv6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angle-right" {...props}></Icon>
