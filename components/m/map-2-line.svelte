<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq73-t5vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq73-t5vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-2-line" {...props}></Icon>
