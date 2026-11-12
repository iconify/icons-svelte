<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ew7caks.css';
import '../../css/h/hrxhp9b1x.css';
import '../../css/q/qp9ttxbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3ew7caks"/><path class="hrxhp9b1x"/><path class="qp9ttxbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firebase" {...props}></Icon>
