<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkpxdacxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xkpxdacxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:checked" {...props}></Icon>
