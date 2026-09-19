<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry5blwf-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ry5blwf-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:ok-circle" {...props}></Icon>
