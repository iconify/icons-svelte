<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxfx58bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxfx58bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rubel-2-line" {...props}></Icon>
