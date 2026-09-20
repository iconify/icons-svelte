<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmkw2to-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmkw2to-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-clock-outline" {...props}></Icon>
