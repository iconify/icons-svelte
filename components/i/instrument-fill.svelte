<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq5d24bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5d24bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:instrument-fill" {...props}></Icon>
