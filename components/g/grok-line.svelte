<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl0xmxbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0xmxbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grok-line" {...props}></Icon>
