<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1u63nvrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1u63nvrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edge-line" {...props}></Icon>
