<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l64f97bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l64f97bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-4-line" {...props}></Icon>
