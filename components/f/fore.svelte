<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlxa5ophx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlxa5ophx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fore" {...props}></Icon>
