<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_oxmr3lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_oxmr3lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eyeglass-fill" {...props}></Icon>
