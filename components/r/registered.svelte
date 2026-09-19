<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyu5r4bdv.css';
import '../../css/g/guh-_zb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu5r4bdv"/><path class="guh-_zb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:registered" {...props}></Icon>
