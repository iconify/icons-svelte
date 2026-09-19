<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_eh_ihjp.css';
import '../../css/u/u7ypgqgoe.css';
import '../../css/a/a19wo66mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w_eh_ihjp"/><path class="u7ypgqgoe"/><path class="a19wo66mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3d-curve-manual" {...props}></Icon>
