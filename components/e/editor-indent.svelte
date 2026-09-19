<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jso90vbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jso90vbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-indent" {...props}></Icon>
