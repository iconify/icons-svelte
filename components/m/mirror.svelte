<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pghnx8bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pghnx8bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mirror" {...props}></Icon>
