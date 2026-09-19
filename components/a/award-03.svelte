<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id7gw1cir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id7gw1cir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:award-03" {...props}></Icon>
