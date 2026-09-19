<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvius29ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvius29ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:direction-left-01" {...props}></Icon>
