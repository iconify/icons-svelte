<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcy_mewmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcy_mewmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lasso-2-line" {...props}></Icon>
