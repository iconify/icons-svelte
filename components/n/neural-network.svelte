<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjtrnul4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjtrnul4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:neural-network" {...props}></Icon>
