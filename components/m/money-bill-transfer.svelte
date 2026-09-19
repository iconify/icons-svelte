<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0otvhb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="y0otvhb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-transfer" {...props}></Icon>
