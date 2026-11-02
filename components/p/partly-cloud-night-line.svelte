<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv-oyfphh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv-oyfphh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-night-line" {...props}></Icon>
