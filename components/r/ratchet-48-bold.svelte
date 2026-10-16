<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsc_0ebep.css';
import '../../css/u/ukrjy-bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wsc_0ebep"/><path class="ukrjy-bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ratchet-48-bold" {...props}></Icon>
