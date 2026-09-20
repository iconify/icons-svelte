<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnvtnnk5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lnvtnnk5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ethernet-port-in-rounded-square" {...props}></Icon>
