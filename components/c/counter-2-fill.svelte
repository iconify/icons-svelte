<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeusycbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeusycbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:counter-2-fill" {...props}></Icon>
