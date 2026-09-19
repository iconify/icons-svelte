<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pntcq57kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pntcq57kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-arrow-up" {...props}></Icon>
