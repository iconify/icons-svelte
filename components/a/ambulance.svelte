<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbl37cbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nbl37cbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ambulance" {...props}></Icon>
