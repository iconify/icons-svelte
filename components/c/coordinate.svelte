<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8diq5roc.css';
import '../../css/x/xko87bc4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q8diq5roc"/><path class="xko87bc4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:coordinate" {...props}></Icon>
