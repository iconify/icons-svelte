<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6rs2wg2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rs2wg2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-hexagon-solid" {...props}></Icon>
