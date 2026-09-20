<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt6330zrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt6330zrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bounding-box" {...props}></Icon>
