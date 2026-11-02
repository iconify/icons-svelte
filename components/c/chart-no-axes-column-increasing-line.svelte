<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfi3xabjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfi3xabjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-column-increasing-line" {...props}></Icon>
