<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_p3wqir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_p3wqir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:base-station-fill" {...props}></Icon>
