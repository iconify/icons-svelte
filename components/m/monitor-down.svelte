<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gvgfizscx.css';
import '../../css/p/p-0qo7b4o.css';
import '../../css/r/r-2g5hbst.css';
import '../../css/h/hvevppabr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gvgfizscx"/><path class="p-0qo7b4o"/><path class="r-2g5hbst"/><path class="hvevppabr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monitor-down" {...props}></Icon>
