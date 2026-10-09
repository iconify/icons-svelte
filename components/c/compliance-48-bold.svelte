<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4447fbqf.css';
import '../../css/w/w4k41-hew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4447fbqf"/><path class="w4k41-hew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compliance-48-bold" {...props}></Icon>
