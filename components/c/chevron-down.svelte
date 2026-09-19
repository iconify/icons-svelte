<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eabxhopre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1312};
const content = `<path class="eabxhopre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-down" {...props}></Icon>
