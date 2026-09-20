<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc8tn-bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc8tn-bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:content-ai-line" {...props}></Icon>
