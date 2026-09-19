<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgx4fhnbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mgx4fhnbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:analytics-reference" {...props}></Icon>
