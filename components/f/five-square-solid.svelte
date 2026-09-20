<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l70wn9y2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l70wn9y2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:five-square-solid" {...props}></Icon>
