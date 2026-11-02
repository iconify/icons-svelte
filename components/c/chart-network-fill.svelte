<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzw_b9byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzw_b9byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-network-fill" {...props}></Icon>
