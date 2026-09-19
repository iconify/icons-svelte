<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i14aqqblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i14aqqblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:new-folder" {...props}></Icon>
