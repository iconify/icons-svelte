<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzbpy1ouj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzbpy1ouj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:filter" {...props}></Icon>
