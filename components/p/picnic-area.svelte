<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d80gbh72b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d80gbh72b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:picnic-area" {...props}></Icon>
