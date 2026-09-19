<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-s_d2w1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-s_d2w1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-data-power" {...props}></Icon>
