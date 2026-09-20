<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn2_-vbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn2_-vbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-no-axes-column-increasing-solid" {...props}></Icon>
