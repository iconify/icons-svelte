<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w503hc0gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w503hc0gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:function-math" {...props}></Icon>
