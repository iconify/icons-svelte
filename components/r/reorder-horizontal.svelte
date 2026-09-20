<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdu0l2a4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdu0l2a4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reorder-horizontal" {...props}></Icon>
