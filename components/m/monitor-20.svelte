<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1uql4bun.css';
import '../../css/s/s4qd1rblb.css';
import '../../css/a/a19dqulkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p1uql4bun"/><path class="s4qd1rblb"/><path class="a19dqulkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-20" {...props}></Icon>
