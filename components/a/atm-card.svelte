<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3l2h_b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3l2h_b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:atm-card" {...props}></Icon>
