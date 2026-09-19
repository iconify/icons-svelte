<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf5fmya5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lf5fmya5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pennant" {...props}></Icon>
