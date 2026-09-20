<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drno9514e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drno9514e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:encryption-outline" {...props}></Icon>
