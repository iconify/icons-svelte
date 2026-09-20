<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2zig3b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2zig3b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:copy" {...props}></Icon>
