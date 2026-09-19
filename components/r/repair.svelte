<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn7qp0y5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tn7qp0y5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:repair" {...props}></Icon>
