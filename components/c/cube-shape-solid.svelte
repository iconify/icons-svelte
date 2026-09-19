<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1m-wck-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e1m-wck-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:cube-shape-solid" {...props}></Icon>
