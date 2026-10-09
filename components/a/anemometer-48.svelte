<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9gapcbyd.css';
import '../../css/x/xx5tdhvbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l9gapcbyd"/><path class="xx5tdhvbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anemometer-48" {...props}></Icon>
