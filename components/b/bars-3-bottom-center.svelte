<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpi02u7-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpi02u7-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bars-3-bottom-center" {...props}></Icon>
