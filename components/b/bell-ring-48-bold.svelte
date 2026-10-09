<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxk_vcban.css';
import '../../css/f/fy_4q-bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wxk_vcban"/><path class="fy_4q-bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-ring-48-bold" {...props}></Icon>
