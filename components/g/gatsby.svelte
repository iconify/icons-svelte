<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dekr_0bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dekr_0bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gatsby" {...props}></Icon>
