<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-r4rkboe.css';
import '../../css/x/xyuv38bch.css';
import '../../css/v/vi1bm7b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-r4rkboe"/><path class="xyuv38bch"/><path class="vi1bm7b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-for-education" {...props}></Icon>
