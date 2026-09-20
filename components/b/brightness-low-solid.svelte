<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1t0mblgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1t0mblgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brightness-low-solid" {...props}></Icon>
