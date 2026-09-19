<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipejqhtoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipejqhtoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:floorshade" {...props}></Icon>
