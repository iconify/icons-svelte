<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_vn6zxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd_vn6zxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:analytics-03" {...props}></Icon>
