<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_5yqbc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_5yqbc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-out-control-point-line" {...props}></Icon>
