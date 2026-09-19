<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2x2vid8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q2x2vid8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:indent-first-line" {...props}></Icon>
