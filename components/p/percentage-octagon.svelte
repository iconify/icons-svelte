<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_x-girrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_x-girrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-octagon" {...props}></Icon>
