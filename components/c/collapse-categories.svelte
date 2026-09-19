<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf66svvni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xf66svvni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:collapse-categories" {...props}></Icon>
