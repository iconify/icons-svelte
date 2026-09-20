<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f25r_yb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f25r_yb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dashboard-gauge-2" {...props}></Icon>
