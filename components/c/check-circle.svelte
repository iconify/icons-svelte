<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl5uzhbhz.css';
import '../../css/t/t0-t7obvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="t0-t7obvm wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:check-circle" {...props}></Icon>
