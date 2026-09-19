<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3hzlzbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t3hzlzbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-planning-waterfall" {...props}></Icon>
