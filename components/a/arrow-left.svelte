<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1537y6xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1537y6xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-left" {...props}></Icon>
