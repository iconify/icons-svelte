<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj8ezo3zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uj8ezo3zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calls-all" {...props}></Icon>
