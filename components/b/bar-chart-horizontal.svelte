<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbxo19bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbxo19bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bar-chart-horizontal" {...props}></Icon>
