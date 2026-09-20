<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2bcowb-l.css';
import '../../css/i/i1sbddona.css';
import '../../css/b/bb7p9ybfb.css';
import '../../css/i/ioqkhfb3p.css';
import '../../css/g/g320chzxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k2bcowb-l"/><path class="i1sbddona"/><path class="bb7p9ybfb"/><path class="ioqkhfb3p"/><path class="g320chzxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:booklogr" {...props}></Icon>
