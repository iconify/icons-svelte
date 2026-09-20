<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xts69-brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xts69-brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:checkmark-double" {...props}></Icon>
