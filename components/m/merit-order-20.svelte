<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2fl-ght.css';
import '../../css/v/vurhcwkho.css';
import '../../css/r/rkgzl8y0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="vurhcwkho"/><path class="rkgzl8y0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:merit-order-20" {...props}></Icon>
