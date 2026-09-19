<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xq777kb9z.css';
import '../../css/t/tj4xg5bkf.css';
import '../../css/p/p7q04xb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xq777kb9z"/><path class="tj4xg5bkf"/><path class="p7q04xb2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:medal-01" {...props}></Icon>
