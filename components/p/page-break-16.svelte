<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9jxoghdq.css';
import '../../css/a/a12aw-hic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c9jxoghdq"/><path class="a12aw-hic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:page-break-16" {...props}></Icon>
