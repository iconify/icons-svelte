<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ycu4_ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8ycu4_ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-down-right-fill" {...props}></Icon>
