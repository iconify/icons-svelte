<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8t7ilbin.css';
import '../../css/n/nxzuucrxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8t7ilbin"/><path class="nxzuucrxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:baffled2" {...props}></Icon>
