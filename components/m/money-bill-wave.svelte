<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym70cwagl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ym70cwagl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:money-bill-wave" {...props}></Icon>
