<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofhx-bc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhx-bc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drop-circle" {...props}></Icon>
