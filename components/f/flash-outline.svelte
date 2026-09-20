<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uup9sabri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uup9sabri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-outline" {...props}></Icon>
