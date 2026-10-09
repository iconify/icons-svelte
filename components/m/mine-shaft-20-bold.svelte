<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvjm-6b1r.css';
import '../../css/h/hn820sblx.css';
import '../../css/w/wkidug_7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mvjm-6b1r"/><path class="hn820sblx"/><path class="wkidug_7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-shaft-20-bold" {...props}></Icon>
