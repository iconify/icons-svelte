<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rprjw-xhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rprjw-xhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-right-solid" {...props}></Icon>
