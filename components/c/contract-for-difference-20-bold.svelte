<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccsyvk3j.css';
import '../../css/y/yz82tw-9z.css';
import '../../css/g/gm0aa1bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="yz82tw-9z"/><path class="gm0aa1bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-for-difference-20-bold" {...props}></Icon>
