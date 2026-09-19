<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo0y1z5yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qo0y1z5yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:italic" {...props}></Icon>
