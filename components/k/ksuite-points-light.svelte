<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og_f3_bmu.css';
import '../../css/w/waab1-svo.css';
import '../../css/e/e-s8zybio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="og_f3_bmu"/><path class="waab1-svo"/><path class="e-s8zybio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-points-light" {...props}></Icon>
