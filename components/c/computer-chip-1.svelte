<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdqx3fz-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vdqx3fz-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-chip-1" {...props}></Icon>
