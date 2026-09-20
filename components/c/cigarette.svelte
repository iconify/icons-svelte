<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0u1r3r5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0u1r3r5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cigarette" {...props}></Icon>
