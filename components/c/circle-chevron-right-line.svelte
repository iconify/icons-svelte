<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr4tq0brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr4tq0brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-chevron-right-line" {...props}></Icon>
