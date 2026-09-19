<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwzqo-bou.css';
import '../../css/d/dt1emtbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwzqo-bou"/><path class="dt1emtbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:return-down-back" {...props}></Icon>
