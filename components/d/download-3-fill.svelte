<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni-8--job.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni-8--job"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-3-fill" {...props}></Icon>
