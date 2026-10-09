<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxs8orj.css';
import '../../css/r/rmqrb06os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="rmqrb06os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-48" {...props}></Icon>
