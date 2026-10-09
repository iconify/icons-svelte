<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymn_1dbbh.css';
import '../../css/n/ndusirsyt.css';
import '../../css/r/r_v2nxmlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ymn_1dbbh"/><path class="ndusirsyt"/><path class="r_v2nxmlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-flow-48-bold" {...props}></Icon>
