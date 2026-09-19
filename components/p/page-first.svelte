<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxmn-r4xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cxmn-r4xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:page-first" {...props}></Icon>
