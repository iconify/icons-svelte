<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwfpi0bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="wwfpi0bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-audio" {...props}></Icon>
