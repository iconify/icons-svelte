<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5xq4ubgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y5xq4ubgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-vis-3" {...props}></Icon>
