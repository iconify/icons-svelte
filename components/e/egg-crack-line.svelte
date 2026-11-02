<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxkwk3bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxkwk3bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-crack-line" {...props}></Icon>
