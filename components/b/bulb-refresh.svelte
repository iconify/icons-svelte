<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_q5-s7-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_q5-s7-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-refresh" {...props}></Icon>
