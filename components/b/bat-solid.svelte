<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk9ov5cxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9ov5cxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bat-solid" {...props}></Icon>
