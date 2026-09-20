<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-3xb2--v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-3xb2--v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:low-priority" {...props}></Icon>
