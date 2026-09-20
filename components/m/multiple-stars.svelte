<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akp-j5wvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="akp-j5wvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:multiple-stars" {...props}></Icon>
