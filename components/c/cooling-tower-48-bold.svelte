<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhnl4rs5r.css';
import '../../css/c/cj33u3imh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qhnl4rs5r"/><path class="cj33u3imh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cooling-tower-48-bold" {...props}></Icon>
