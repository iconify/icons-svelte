<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o053b3bvz.css';
import '../../css/b/bps76ebgq.css';
import '../../css/f/fw1xawbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o053b3bvz"/><path class="bps76ebgq"/><path class="fw1xawbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calendar-briefcase" {...props}></Icon>
