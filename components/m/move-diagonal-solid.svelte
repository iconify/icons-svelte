<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4t88lbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4t88lbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-diagonal-solid" {...props}></Icon>
