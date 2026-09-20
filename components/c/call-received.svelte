<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlu5le0mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlu5le0mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-received" {...props}></Icon>
