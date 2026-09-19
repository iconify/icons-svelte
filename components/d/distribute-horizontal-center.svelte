<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g60ywcbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g60ywcbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:distribute-horizontal-center" {...props}></Icon>
