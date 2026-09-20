<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/y/y3vr5wbqc.css';
import '../../css/p/p-t1syddl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="pr52f_b5y"><path class="y3vr5wbqc"/><path class="p-t1syddl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:download-arrow" {...props}></Icon>
