<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2uy8o19f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2uy8o19f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:base-station-line" {...props}></Icon>
