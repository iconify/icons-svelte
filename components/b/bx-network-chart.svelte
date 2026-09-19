<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iswl_3bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iswl_3bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-network-chart" {...props}></Icon>
