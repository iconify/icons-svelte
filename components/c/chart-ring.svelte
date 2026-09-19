<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir8nhuf2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ir8nhuf2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-ring" {...props}></Icon>
