<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8h5bgb-m.css';
import '../../css/n/n_xpcc89w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8h5bgb-m"/><path class="n_xpcc89w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nimtable-light" {...props}></Icon>
