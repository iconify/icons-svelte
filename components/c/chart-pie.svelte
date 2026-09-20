<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo_m8-b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo_m8-b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chart-pie" {...props}></Icon>
