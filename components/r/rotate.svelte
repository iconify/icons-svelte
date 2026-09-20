<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvv0too7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hvv0too7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:rotate" {...props}></Icon>
