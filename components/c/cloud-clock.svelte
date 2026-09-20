<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7n7n7t2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7n7n7t2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-clock" {...props}></Icon>
