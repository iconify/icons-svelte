<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxq2d1-sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq2d1-sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:event-minus" {...props}></Icon>
