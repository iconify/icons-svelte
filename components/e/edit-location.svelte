<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6bak0nwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6bak0nwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:edit-location" {...props}></Icon>
