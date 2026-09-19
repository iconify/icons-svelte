<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omn6do9zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="omn6do9zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array-decimal" {...props}></Icon>
