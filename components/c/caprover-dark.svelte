<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_jc64d5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_jc64d5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caprover-dark" {...props}></Icon>
