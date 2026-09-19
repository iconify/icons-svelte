<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1vjxgbrn.css';
import '../../css/j/j2qx5-bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s1vjxgbrn"/><path class="j2qx5-bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:alarm-clock" {...props}></Icon>
