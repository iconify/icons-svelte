<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwtoqccjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xwtoqccjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:iso" {...props}></Icon>
