<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0tww8tsi.css';
import '../../css/a/azjk1obih.css';
import '../../css/y/y_yvwz1md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l0tww8tsi"/><path class="azjk1obih"/><path class="y_yvwz1md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-off-48" {...props}></Icon>
