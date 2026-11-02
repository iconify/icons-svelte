<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q93vyn7tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q93vyn7tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-11-line" {...props}></Icon>
