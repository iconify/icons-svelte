<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-dao-bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="g-dao-bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-return" {...props}></Icon>
