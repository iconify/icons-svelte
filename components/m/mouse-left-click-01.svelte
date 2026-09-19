<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pyyynhfqd.css';
import '../../css/f/f6hdfiifw.css';
import '../../css/j/j7hywqb8i.css';
import '../../css/u/u7cc7wb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pyyynhfqd"/><path class="f6hdfiifw"/><path class="j7hywqb8i"/><path class="u7cc7wb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-left-click-01" {...props}></Icon>
