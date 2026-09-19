<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk5o7kbjs.css';
import '../../css/v/vem7gutod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jk5o7kbjs"/><path class="vem7gutod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-measurement" {...props}></Icon>
