<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rte55_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1rte55_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:move" {...props}></Icon>
