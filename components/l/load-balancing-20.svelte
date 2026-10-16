<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1osud8tz.css';
import '../../css/s/spvzilqpr.css';
import '../../css/a/aqd5nkwct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j1osud8tz"/><path class="spvzilqpr"/><path class="aqd5nkwct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-balancing-20" {...props}></Icon>
