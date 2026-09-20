<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msrdi5bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msrdi5bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-pause" {...props}></Icon>
