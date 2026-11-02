<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oub0p0bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oub0p0bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-scatter-fill" {...props}></Icon>
