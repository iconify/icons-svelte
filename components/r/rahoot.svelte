<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv390hq8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pv390hq8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rahoot" {...props}></Icon>
