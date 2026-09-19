<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7_v91bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d7_v91bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:asm" {...props}></Icon>
