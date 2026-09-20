<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku_-c03pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku_-c03pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piler" {...props}></Icon>
