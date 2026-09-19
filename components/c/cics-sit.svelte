<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpje9lbhk.css';
import '../../css/r/rkrmrebfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpje9lbhk"/><path class="rkrmrebfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-sit" {...props}></Icon>
