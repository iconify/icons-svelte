<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qlu58ik7m.css';
import '../../css/a/assxj4gal.css';
import '../../css/x/xzjhvcb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qlu58ik7m"/><path class="assxj4gal"/><path class="xzjhvcb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bicycle-01" {...props}></Icon>
