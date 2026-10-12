<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dds28brcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dds28brcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paperclip-20" {...props}></Icon>
