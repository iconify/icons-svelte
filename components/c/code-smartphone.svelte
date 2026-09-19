<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spvfrgbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="spvfrgbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:code-smartphone" {...props}></Icon>
