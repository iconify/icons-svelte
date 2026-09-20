<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-6xlb0ma.css';
import '../../css/j/jxxo5_2qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-6xlb0ma"/><path class="jxxo5_2qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-assistant" {...props}></Icon>
