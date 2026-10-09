<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5yiolbrq.css';
import '../../css/q/qsgv5bbpc.css';
import '../../css/z/zf9x55bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5yiolbrq"/><path class="qsgv5bbpc"/><path class="zf9x55bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layers-20-bold" {...props}></Icon>
