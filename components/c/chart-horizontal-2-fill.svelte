<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-0mgqb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-0mgqb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-2-fill" {...props}></Icon>
