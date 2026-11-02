<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5izf94kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5izf94kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:horn-2-line" {...props}></Icon>
