<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkj37h9sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xkj37h9sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:anonymous" {...props}></Icon>
