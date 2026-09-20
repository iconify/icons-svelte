<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl7p-6xcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl7p-6xcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle-1" {...props}></Icon>
