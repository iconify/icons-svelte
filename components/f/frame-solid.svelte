<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mak4hx3pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mak4hx3pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:frame-solid" {...props}></Icon>
