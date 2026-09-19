<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwq5s_bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwq5s_bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pool-electric-lvl" {...props}></Icon>
