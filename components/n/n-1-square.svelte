<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub7f00uxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ub7f00uxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:n-1-square" {...props}></Icon>
