<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6knx5ati.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6knx5ati"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-line-fill" {...props}></Icon>
