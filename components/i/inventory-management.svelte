<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-mit6byn.css';
import '../../css/c/cro928b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-mit6byn"/><path class="cro928b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:inventory-management" {...props}></Icon>
