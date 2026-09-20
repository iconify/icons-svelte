<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvb524s4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dvb524s4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bolt" {...props}></Icon>
