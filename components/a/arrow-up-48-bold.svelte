<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2l8ftbhe.css';
import '../../css/p/pjj956y7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2l8ftbhe"/><path class="pjj956y7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-48-bold" {...props}></Icon>
