<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3b3aw3dq.css';
import '../../css/w/wzf1vhbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j3b3aw3dq"/><path class="wzf1vhbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:environmental-impact-48" {...props}></Icon>
