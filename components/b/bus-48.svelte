<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg7q3o5tc.css';
import '../../css/y/y6xsb0p_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xg7q3o5tc"/><path class="y6xsb0p_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bus-48" {...props}></Icon>
