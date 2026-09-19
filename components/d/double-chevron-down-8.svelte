<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm6_xo21q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hm6_xo21q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-chevron-down-8" {...props}></Icon>
