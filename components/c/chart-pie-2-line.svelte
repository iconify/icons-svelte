<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg1poxbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1poxbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-2-line" {...props}></Icon>
