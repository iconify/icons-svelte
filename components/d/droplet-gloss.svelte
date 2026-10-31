<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqeu97e5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqeu97e5j wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplet-gloss" {...props}></Icon>
