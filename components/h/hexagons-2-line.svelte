<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qblh994vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qblh994vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagons-2-line" {...props}></Icon>
