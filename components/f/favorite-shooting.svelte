<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn04et98e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn04et98e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-shooting" {...props}></Icon>
