<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-mxqeckc.css';
import '../../css/x/xam7olb4z.css';
import '../../css/w/wt22uxb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x-mxqeckc"/><path clip-rule="evenodd" class="xam7olb4z"/><path clip-rule="evenodd" class="wt22uxb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-smooth-right-16" {...props}></Icon>
