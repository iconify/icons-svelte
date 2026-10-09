<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q07t0ebtb.css';
import '../../css/s/sjt-1kaax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q07t0ebtb"/><path class="sjt-1kaax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-warning-20-bold" {...props}></Icon>
