<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdilfab6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zdilfab6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gif" {...props}></Icon>
