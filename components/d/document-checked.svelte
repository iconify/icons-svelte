<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggbpz7_sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ggbpz7_sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:document-checked" {...props}></Icon>
