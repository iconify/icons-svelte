<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj55e6wen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aj55e6wen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-aa-large" {...props}></Icon>
