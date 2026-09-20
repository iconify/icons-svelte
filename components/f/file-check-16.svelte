<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9nn-b3_g.css';
import '../../css/p/p6k-85b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x9nn-b3_g"/><path class="p6k-85b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-check-16" {...props}></Icon>
