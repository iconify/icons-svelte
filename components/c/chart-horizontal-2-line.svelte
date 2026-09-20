<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubzqx4l4f.css';
import '../../css/d/dnxa5bcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubzqx4l4f"/><path class="dnxa5bcqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-2-line" {...props}></Icon>
