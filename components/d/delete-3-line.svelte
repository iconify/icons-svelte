<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2d_n-b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2d_n-b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-3-line" {...props}></Icon>
