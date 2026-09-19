<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbjht8bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kbjht8bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-add" {...props}></Icon>
