<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmlcddcrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmlcddcrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:funnel-minus" {...props}></Icon>
