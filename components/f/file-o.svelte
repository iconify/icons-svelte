<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry_x50bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="ry_x50bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-o" {...props}></Icon>
