<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqjywxbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqjywxbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:resize-width" {...props}></Icon>
