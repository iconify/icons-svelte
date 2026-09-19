<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvryw38cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvryw38cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pizza-slice" {...props}></Icon>
