<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/digtmc1gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="digtmc1gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:node-red" {...props}></Icon>
