<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji14mos9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji14mos9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-off" {...props}></Icon>
