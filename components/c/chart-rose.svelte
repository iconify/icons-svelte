<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-7nv8f5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-7nv8f5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-rose" {...props}></Icon>
