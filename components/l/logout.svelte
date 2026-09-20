<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rra8vxnmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rra8vxnmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:logout" {...props}></Icon>
