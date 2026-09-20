<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk94mmbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jk94mmbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rectangle" {...props}></Icon>
