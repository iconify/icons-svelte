<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on92ny6gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="on92ny6gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-volume" {...props}></Icon>
