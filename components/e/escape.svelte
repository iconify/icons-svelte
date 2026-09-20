<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuxrjdbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wuxrjdbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:escape" {...props}></Icon>
