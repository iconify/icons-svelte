<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjn-p1eni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sjn-p1eni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:maximize" {...props}></Icon>
