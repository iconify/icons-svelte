<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr78b8bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr78b8bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pavilion-line" {...props}></Icon>
