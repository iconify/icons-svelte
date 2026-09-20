<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulx72ubuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulx72ubuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-excel" {...props}></Icon>
