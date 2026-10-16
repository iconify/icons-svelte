<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0xks__8y.css';
import '../../css/m/ma-nqn8dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0xks__8y"/><path class="ma-nqn8dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-reducer-20-bold" {...props}></Icon>
