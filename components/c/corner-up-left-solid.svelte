<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0_ge5bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0_ge5bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-up-left-solid" {...props}></Icon>
