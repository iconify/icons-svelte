<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5me6jn8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l5me6jn8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:palm" {...props}></Icon>
