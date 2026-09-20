<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkitgic2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkitgic2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-left-down-line" {...props}></Icon>
