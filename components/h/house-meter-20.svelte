<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7juawdew.css';
import '../../css/d/d2axpfabm.css';
import '../../css/m/mmo1ocbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="d2axpfabm"/><path class="mmo1ocbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-meter-20" {...props}></Icon>
