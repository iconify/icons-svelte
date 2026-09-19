<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf0f2gbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yf0f2gbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:rotate-left" {...props}></Icon>
