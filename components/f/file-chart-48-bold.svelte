<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdos38jip.css';
import '../../css/n/n8-1wd4lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="n8-1wd4lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-chart-48-bold" {...props}></Icon>
