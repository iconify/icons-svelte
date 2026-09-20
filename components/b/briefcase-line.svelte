<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0i450_ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0i450_ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-line" {...props}></Icon>
