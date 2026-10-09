<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir4g1b6-s.css';
import '../../css/w/w0_dqt_cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ir4g1b6-s"/><path class="w0_dqt_cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-to-line-20-bold" {...props}></Icon>
