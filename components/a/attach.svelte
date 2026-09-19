<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4pxh1bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d4pxh1bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:attach" {...props}></Icon>
