<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co8z4ybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co8z4ybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:plug-filled" {...props}></Icon>
