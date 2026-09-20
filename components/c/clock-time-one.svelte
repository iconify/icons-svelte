<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il5vivbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il5vivbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-one" {...props}></Icon>
