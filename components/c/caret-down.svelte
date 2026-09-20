<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clk1bdckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clk1bdckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:caret-down" {...props}></Icon>
