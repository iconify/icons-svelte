<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc4olvb8c.css';
import '../../css/e/el8rvydxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fc4olvb8c"/><path class="el8rvydxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-transformer-48" {...props}></Icon>
