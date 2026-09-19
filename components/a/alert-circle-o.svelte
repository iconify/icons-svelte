<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyhrs9bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="qyhrs9bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alert-circle-o" {...props}></Icon>
