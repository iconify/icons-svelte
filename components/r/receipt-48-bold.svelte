<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4s-jblr.css';
import '../../css/q/qftg15_vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="qftg15_vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-48-bold" {...props}></Icon>
