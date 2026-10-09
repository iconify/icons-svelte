<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laierucpu.css';
import '../../css/y/y_bkliy_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="laierucpu"/><path class="y_bkliy_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crucible-48-bold" {...props}></Icon>
