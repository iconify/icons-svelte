<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkjb6_06b.css';
import '../../css/y/y--yqbbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nkjb6_06b"/><path class="y--yqbbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-loop-left" {...props}></Icon>
