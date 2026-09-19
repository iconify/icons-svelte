<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cbr0shbpp.css';
import '../../css/t/tqi_khm-q.css';
import '../../css/i/ilxf184hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cbr0shbpp"/><path class="tqi_khm-q"/><path class="ilxf184hs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:punching-ball-01" {...props}></Icon>
