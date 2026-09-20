<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpv-gzbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpv-gzbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:compose" {...props}></Icon>
