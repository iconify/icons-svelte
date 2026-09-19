<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5q3_ps6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n5q3_ps6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:flick-left" {...props}></Icon>
