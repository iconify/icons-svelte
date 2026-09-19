<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0unw79-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000.658,"height":1000};
const content = `<path class="j0unw79-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:googleplus-rect" {...props}></Icon>
