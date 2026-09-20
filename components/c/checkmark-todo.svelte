<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsk7nvgoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="dsk7nvgoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:checkmark-todo" {...props}></Icon>
