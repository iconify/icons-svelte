<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9xskgb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9xskgb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-chart-pie" {...props}></Icon>
