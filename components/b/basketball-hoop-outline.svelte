<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-7kixbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-7kixbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:basketball-hoop-outline" {...props}></Icon>
