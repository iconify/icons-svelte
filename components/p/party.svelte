<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmd0fo11n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmd0fo11n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:party" {...props}></Icon>
