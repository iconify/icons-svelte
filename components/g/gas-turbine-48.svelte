<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob-pomunx.css';
import '../../css/v/vq2he1abb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ob-pomunx"/><path class="vq2he1abb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-turbine-48" {...props}></Icon>
