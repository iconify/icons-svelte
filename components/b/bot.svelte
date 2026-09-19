<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siav9f5cp.css';
import '../../css/j/jjcws580t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="siav9f5cp"/><path class="jjcws580t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bot" {...props}></Icon>
