<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0yw_i1yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0yw_i1yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:report-line" {...props}></Icon>
