<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at_qv4_-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="at_qv4_-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gantt-chart-solid" {...props}></Icon>
