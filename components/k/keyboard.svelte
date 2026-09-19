<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6r_bpbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1344};
const content = `<path class="a6r_bpbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:keyboard" {...props}></Icon>
