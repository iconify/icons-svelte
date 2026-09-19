<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge1l8697w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ge1l8697w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-8" {...props}></Icon>
