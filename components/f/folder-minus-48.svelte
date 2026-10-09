<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb9x9-c_l.css';
import '../../css/j/jp5w86lrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/><path class="jp5w86lrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-minus-48" {...props}></Icon>
