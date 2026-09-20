<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgqkpwb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgqkpwb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:3d-rotation" {...props}></Icon>
