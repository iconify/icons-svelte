<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm4isn3js.css';
import '../../css/y/y711oejcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gm4isn3js"/><path class="y711oejcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-ceiling" {...props}></Icon>
