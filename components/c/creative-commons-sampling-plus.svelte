<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iopybtbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iopybtbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons-sampling-plus" {...props}></Icon>
