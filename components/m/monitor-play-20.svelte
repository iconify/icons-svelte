<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqxty8b1p.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/x/xuhpwqi5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqxty8b1p"/><path class="kvl9ucc0s"/><path class="xuhpwqi5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-play-20" {...props}></Icon>
