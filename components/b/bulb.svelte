<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4e5-gbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="x4e5-gbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:bulb" {...props}></Icon>
