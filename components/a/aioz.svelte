<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxqaj3bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqaj3bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aioz" {...props}></Icon>
