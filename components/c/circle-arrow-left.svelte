<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrk2c_o7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mrk2c_o7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:circle-arrow-left" {...props}></Icon>
