<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezwopb-j.css';
import '../../css/y/y2_5hqbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="y2_5hqbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-chart-48" {...props}></Icon>
