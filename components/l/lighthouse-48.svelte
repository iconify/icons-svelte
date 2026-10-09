<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh9p_6w5s.css';
import '../../css/y/y2yxtt6_c.css';
import '../../css/l/lhb-r0bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yh9p_6w5s"/><path class="y2yxtt6_c"/><path class="lhb-r0bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lighthouse-48" {...props}></Icon>
