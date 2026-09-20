<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnf2_ub3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnf2_ub3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-x-inside-solid" {...props}></Icon>
