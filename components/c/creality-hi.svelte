<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx0rqwbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx0rqwbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:creality-hi" {...props}></Icon>
