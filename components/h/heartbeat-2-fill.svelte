<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1ncrwq7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ncrwq7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-2-fill" {...props}></Icon>
