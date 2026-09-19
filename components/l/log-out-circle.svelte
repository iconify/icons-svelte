<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeah8-6tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeah8-6tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:log-out-circle" {...props}></Icon>
