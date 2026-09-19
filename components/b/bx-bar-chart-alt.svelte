<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2wqd55dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2wqd55dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bar-chart-alt" {...props}></Icon>
