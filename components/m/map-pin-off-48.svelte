<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xneu8q3zz.css';
import '../../css/n/n5wvztb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xneu8q3zz"/><path class="n5wvztb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-off-48" {...props}></Icon>
