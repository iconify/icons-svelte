<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw8xyyw2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw8xyyw2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grid-table" {...props}></Icon>
