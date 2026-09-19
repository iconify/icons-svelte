<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cafiwfqjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="cafiwfqjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:copy" {...props}></Icon>
