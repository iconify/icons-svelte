<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi_6xzbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_6xzbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:funnel" {...props}></Icon>
