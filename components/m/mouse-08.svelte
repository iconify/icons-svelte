<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c1t6ucbve.css';
import '../../css/d/d9x6ewbln.css';
import '../../css/q/qzm5wp94p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c1t6ucbve"/><path class="d9x6ewbln"/><path class="qzm5wp94p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-08" {...props}></Icon>
