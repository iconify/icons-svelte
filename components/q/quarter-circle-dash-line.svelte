<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln7uv3d2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln7uv3d2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quarter-circle-dash-line" {...props}></Icon>
