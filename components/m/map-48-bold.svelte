<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qee7o7hwy.css';
import '../../css/r/rchtrhc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qee7o7hwy"/><path class="rchtrhc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-48-bold" {...props}></Icon>
