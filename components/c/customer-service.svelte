<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh61ck4mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rh61ck4mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:customer-service" {...props}></Icon>
