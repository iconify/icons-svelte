<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivo15gtnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ivo15gtnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:report-growth" {...props}></Icon>
