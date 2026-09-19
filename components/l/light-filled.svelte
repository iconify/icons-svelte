<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8yr7obhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z8yr7obhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:light-filled" {...props}></Icon>
