<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nswvf6xsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nswvf6xsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:diagram" {...props}></Icon>
