<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp2o07q1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yp2o07q1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-vis-1" {...props}></Icon>
