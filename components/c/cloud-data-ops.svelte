<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcp9bc3cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tcp9bc3cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-data-ops" {...props}></Icon>
