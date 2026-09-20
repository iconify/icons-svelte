<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vph7o5b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vph7o5b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fire-hydrant-alert" {...props}></Icon>
