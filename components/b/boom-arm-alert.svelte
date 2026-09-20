<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sydwlsbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sydwlsbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boom-arm-alert" {...props}></Icon>
