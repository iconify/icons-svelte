<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nutwix95i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nutwix95i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:octahedron-off" {...props}></Icon>
