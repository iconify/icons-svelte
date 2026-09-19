<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3-ktby_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l3-ktby_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cursor-1" {...props}></Icon>
