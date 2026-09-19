<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jshimbb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="jshimbb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-7-5" {...props}></Icon>
