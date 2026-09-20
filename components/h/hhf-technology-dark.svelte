<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0panmbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0panmbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hhf-technology-dark" {...props}></Icon>
