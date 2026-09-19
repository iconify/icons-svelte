<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0dq21bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n0dq21bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:calendar" {...props}></Icon>
