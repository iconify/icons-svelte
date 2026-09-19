<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ricakl_nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ricakl_nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:plane" {...props}></Icon>
