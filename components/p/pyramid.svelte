<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvu1cpbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvu1cpbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pyramid" {...props}></Icon>
