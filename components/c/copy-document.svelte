<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-due_ykv.css';
import '../../css/v/vwfdbyhuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j-due_ykv"/><path class="vwfdbyhuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:copy-document" {...props}></Icon>
