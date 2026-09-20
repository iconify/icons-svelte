<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhmvr4bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhmvr4bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bell" {...props}></Icon>
