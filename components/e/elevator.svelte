<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1dxpsbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n1dxpsbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:elevator" {...props}></Icon>
