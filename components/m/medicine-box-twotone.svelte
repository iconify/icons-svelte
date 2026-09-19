<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1y0igb8r.css';
import '../../css/j/j48tzybig.css';
import '../../css/t/tz5dmibxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k1y0igb8r"/><path class="j48tzybig"/><path class="tz5dmibxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:medicine-box-twotone" {...props}></Icon>
