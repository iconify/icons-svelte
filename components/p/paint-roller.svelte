<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqut5_rjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqut5_rjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:paint-roller" {...props}></Icon>
