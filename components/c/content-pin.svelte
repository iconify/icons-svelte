<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk-vbsb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bk-vbsb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-pin" {...props}></Icon>
