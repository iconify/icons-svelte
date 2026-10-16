<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av2i24b1f.css';
import '../../css/i/ifjmab6ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="av2i24b1f"/><path class="ifjmab6ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:extension-lead-20" {...props}></Icon>
