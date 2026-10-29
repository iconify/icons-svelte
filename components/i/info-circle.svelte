<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl5uzhbhz.css';
import '../../css/d/d3wfw4b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="d3wfw4b1i wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:info-circle" {...props}></Icon>
