<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmfyb8myx.css';
import '../../css/d/dxwhy-b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmfyb8myx"/><path class="dxwhy-b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-bold" {...props}></Icon>
