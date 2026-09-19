<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_c4xabtr.css';
import '../../css/t/t9axjb05q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_c4xabtr"/><path class="t9axjb05q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:part-definition" {...props}></Icon>
