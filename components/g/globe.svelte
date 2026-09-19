<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sydt2ty0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":496};
const content = `<path class="sydt2ty0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:globe" {...props}></Icon>
