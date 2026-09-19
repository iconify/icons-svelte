<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tij_f1buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tij_f1buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:d3-js" {...props}></Icon>
