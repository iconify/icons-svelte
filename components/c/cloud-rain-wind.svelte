<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wocan8bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wocan8bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-rain-wind" {...props}></Icon>
