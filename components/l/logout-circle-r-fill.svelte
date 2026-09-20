<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsv_9ebej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsv_9ebej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-circle-r-fill" {...props}></Icon>
