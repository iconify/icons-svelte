<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7-dl7bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7-dl7bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-down" {...props}></Icon>
