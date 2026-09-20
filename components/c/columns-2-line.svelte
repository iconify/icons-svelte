<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osrqvu4up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osrqvu4up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-2-line" {...props}></Icon>
