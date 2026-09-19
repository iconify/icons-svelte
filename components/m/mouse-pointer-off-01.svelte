<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md09hy4px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md09hy4px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-pointer-off-01" {...props}></Icon>
