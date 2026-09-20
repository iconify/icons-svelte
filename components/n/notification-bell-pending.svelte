<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pjiztkldl.css';
import '../../css/r/rwmnp2bmg.css';
import '../../css/r/r057cwbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pjiztkldl"/><path class="rwmnp2bmg"/><circle class="r057cwbhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-pending" {...props}></Icon>
