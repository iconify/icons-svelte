<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd5r8wuvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hd5r8wuvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:jewish-14" {...props}></Icon>
