<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_frcb-c.css';
import '../../css/z/z2e46e6lb.css';
import '../../css/k/k03lqnb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path class="z2e46e6lb"/><path class="k03lqnb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eraser-square-bold-duotone" {...props}></Icon>
