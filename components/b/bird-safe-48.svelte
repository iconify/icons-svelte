<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs628n7li.css';
import '../../css/i/is5s5qqcb.css';
import '../../css/r/r5wz4ccht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xs628n7li"/><path class="is5s5qqcb"/><path class="r5wz4ccht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bird-safe-48" {...props}></Icon>
