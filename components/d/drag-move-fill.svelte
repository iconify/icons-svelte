<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1rm31bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1rm31bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drag-move-fill" {...props}></Icon>
