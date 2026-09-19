<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pufuoacsr.css';
import '../../css/o/o1h606vtq.css';
import '../../css/t/ts-4c6cxu.css';
import '../../css/b/bo0gn7djo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pufuoacsr"/><path class="o1h606vtq"/><path class="ts-4c6cxu"/><path class="bo0gn7djo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-tennisball" {...props}></Icon>
