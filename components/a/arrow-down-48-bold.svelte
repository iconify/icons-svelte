<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2l8ftbhe.css';
import '../../css/p/p_7xd_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2l8ftbhe"/><path class="p_7xd_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-48-bold" {...props}></Icon>
