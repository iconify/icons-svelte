<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjz61vw-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a rjz61vw-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:buffer" {...props}></Icon>
