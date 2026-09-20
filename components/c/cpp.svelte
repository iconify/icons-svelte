<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-b1_byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sz-b1_byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cpp" {...props}></Icon>
