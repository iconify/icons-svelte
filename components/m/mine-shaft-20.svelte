<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubnupnbby.css';
import '../../css/z/zbrckdb1x.css';
import '../../css/m/mkvuid9tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubnupnbby"/><path class="zbrckdb1x"/><path class="mkvuid9tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-shaft-20" {...props}></Icon>
