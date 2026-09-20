<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvs2itiwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xvs2itiwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:geometric" {...props}></Icon>
