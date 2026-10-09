<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1qei_b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x1qei_b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-off-48-bold" {...props}></Icon>
