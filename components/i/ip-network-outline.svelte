<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4oxo7lej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4oxo7lej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ip-network-outline" {...props}></Icon>
