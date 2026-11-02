<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfc3j7wuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfc3j7wuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-line" {...props}></Icon>
