<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvv8rja_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mvv8rja_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:constraint" {...props}></Icon>
