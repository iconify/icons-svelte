<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbmd_dbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbmd_dbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:die-3" {...props}></Icon>
