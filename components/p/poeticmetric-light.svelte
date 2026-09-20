<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb-64f8xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb-64f8xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poeticmetric-light" {...props}></Icon>
