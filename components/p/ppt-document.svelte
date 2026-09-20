<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8sgvbc1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8sgvbc1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ppt-document" {...props}></Icon>
