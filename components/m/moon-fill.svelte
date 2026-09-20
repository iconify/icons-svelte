<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf7ojlgcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf7ojlgcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-fill" {...props}></Icon>
