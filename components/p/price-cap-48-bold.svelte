<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpel3hezc.css';
import '../../css/f/f6qp33zwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="f6qp33zwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-cap-48-bold" {...props}></Icon>
